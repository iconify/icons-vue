<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbfrc-9ip.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="mbfrc-9ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:lock-small-solid" /></template>

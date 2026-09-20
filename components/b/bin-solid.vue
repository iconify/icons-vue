<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahqll4bmg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="ahqll4bmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:bin-solid" /></template>

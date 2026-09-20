<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nwmt_xb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="nwmt_xb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:arrow-up-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_zqm_bsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_zqm_bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:flashlight-x" /></template>

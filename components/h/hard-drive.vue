<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pj_hgw7cm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pj_hgw7cm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:hard-drive" /></template>

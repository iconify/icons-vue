<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wgmsu_7-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wgmsu_7-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:download-alt" /></template>

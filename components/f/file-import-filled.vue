<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxzbmtabh.css';
import '../../css/y/y663-_bpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wxzbmtabh"/><path class="y663-_bpd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-import-filled" /></template>

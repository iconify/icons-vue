<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yrmky_bdh.css';
import '../../css/z/zos2k5b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yrmky_bdh"/><path class="zos2k5b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:excited-filled" /></template>

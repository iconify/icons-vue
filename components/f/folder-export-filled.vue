<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t2x1pjb-k.css';
import '../../css/q/qlez1nbos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t2x1pjb-k"/><path class="qlez1nbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:folder-export-filled" /></template>

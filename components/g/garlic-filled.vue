<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/orckkf5mu.css';
import '../../css/u/uiwntpvlg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="orckkf5mu"/><path class="uiwntpvlg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:garlic-filled" /></template>

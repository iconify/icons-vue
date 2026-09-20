<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql3-6mw4a.css';
import '../../css/y/y81vbnbsu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql3-6mw4a"/><path class="y81vbnbsu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:file-blocked-filled" /></template>

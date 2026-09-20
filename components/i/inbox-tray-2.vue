<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zgu1592no.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zgu1592no"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:inbox-tray-2" /></template>

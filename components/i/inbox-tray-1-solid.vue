<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d70ksw_kc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="d70ksw_kc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:inbox-tray-1-solid" /></template>

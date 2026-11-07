<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tj6io99fw.css';
import '../../css/x/xrub8bc1s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tj6io99fw"/><path class="xrub8bc1s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gps-bold" /></template>

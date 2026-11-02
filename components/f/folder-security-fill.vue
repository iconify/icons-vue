<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqt7fdbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqt7fdbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-security-fill" /></template>

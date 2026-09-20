<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gck3udbpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gck3udbpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:history" /></template>

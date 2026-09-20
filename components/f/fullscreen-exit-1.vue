<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x06o34gcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x06o34gcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:fullscreen-exit-1" /></template>

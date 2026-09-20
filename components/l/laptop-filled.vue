<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jryahzlna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jryahzlna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:laptop-filled" /></template>

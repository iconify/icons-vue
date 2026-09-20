<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdd758bbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdd758bbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow2" /></template>

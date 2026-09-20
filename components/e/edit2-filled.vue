<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dil75-s_y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dil75-s_y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:edit2-filled" /></template>

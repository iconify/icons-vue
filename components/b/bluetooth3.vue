<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tdihohbmf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tdihohbmf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bluetooth3" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zka2d_b1v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zka2d_b1v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:driver2" /></template>

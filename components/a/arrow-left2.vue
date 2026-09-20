<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozsgqjbyi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ozsgqjbyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left2" /></template>

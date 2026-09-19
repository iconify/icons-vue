<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xg8exbb1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="xg8exbb1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:amazon" /></template>

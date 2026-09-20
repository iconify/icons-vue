<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_58wgb4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_58wgb4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:ball-bowling" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/byrk5zf9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="byrk5zf9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:dislike-solid" /></template>

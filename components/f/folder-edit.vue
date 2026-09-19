<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i_s6lc4vx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i_s6lc4vx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:folder-edit" /></template>

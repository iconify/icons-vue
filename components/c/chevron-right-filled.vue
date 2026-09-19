<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jw3alemlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jw3alemlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:chevron-right-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hqn6nb3sk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hqn6nb3sk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:file-text-refresh" /></template>

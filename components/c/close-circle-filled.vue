<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ujm-_ywyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujm-_ywyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:close-circle-filled" /></template>

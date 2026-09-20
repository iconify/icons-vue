<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_xr5ubro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_xr5ubro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:basecamp" /></template>

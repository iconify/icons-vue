<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/daw-8pbwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="daw-8pbwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:crown-filled" /></template>

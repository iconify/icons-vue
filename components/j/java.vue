<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-yfbku3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z-yfbku3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:java" /></template>

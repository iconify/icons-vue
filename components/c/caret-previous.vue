<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi2utgblt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hi2utgblt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:caret-previous" /></template>

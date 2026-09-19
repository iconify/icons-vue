<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a87vvobix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a87vvobix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cloud-snow" /></template>

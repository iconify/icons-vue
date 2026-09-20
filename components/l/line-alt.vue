<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0c2gbcdr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o0c2gbcdr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:line-alt" /></template>

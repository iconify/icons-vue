<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j2pw65d4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j2pw65d4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:arrow-up-left" /></template>

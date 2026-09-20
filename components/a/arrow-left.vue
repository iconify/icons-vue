<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b5e20cb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5e20cb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:arrow-left" /></template>

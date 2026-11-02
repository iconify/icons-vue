<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2x-4p21v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2x-4p21v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:arrow-right-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyult47py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyult47py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-up-on-square-stack" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yjfhaw4wq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjfhaw4wq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-justify-fill" /></template>

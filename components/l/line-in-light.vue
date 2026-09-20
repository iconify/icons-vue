<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wt3vlejol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wt3vlejol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:line-in-light" /></template>

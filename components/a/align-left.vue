<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/czgrayb-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="czgrayb-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:align-left" /></template>

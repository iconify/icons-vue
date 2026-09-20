<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y27aw59rn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y27aw59rn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:arrow-rotate" /></template>

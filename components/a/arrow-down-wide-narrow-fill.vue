<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8jk0pi6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8jk0pi6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-down-wide-narrow-fill" /></template>

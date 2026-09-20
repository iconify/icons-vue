<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pm3phgtsy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm3phgtsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:disqus" /></template>

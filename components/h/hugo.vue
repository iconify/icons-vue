<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6935kbuc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6935kbuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:hugo" /></template>

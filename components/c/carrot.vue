<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0-yarbnn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v0-yarbnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:carrot" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7w03rbki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7w03rbki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:addydotio" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftckqgulz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ftckqgulz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bandcamp" /></template>

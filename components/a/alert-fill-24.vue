<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vq8qkhbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vq8qkhbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:alert-fill-24" /></template>

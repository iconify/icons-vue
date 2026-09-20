<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3qxd6b1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3qxd6b1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:home-variant" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjvnp3bmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjvnp3bmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:hotel-search" /></template>

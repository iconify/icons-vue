<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wov6qjbrb.css';
import '../../css/k/kx5tz624c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wov6qjbrb"/><path class="kx5tz624c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:key-24" /></template>

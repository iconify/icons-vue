<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xy1f2qbrw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xy1f2qbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bluesky" /></template>

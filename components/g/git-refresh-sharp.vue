<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxc60ek4g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxc60ek4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:git-refresh-sharp" /></template>

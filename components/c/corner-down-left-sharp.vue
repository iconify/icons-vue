<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/skkqfibng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="skkqfibng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:corner-down-left-sharp" /></template>

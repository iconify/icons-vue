<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4zkhxbic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4zkhxbic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:battery-full-sharp" /></template>

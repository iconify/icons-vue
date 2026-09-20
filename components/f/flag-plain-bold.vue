<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8umd8lyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8umd8lyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:flag-plain-bold" /></template>

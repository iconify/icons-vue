<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdq919bih.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdq919bih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:lemonsqueezy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/macbvkc0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-8,"top":-5};
const content = `<path class="macbvkc0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevron-left" /></template>

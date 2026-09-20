<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/co9nylr9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-3,"top":-2.5};
const content = `<path class="co9nylr9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:filter-f" /></template>

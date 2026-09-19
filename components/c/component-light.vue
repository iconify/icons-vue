<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6t2jv6zz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6t2jv6zz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:component-light" /></template>

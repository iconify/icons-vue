<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyc9jsn5i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyc9jsn5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:divide" /></template>

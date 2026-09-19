<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eoihlxb3o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoihlxb3o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-1-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e32ell92q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e32ell92q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:earbuds-fill" /></template>

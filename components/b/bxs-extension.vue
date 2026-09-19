<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e521f7caz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e521f7caz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-extension" /></template>

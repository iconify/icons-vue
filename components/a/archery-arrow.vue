<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x67dcf5cr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x67dcf5cr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:archery-arrow" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bml9k6b2g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bml9k6b2g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:log-out" /></template>

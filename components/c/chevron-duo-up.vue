<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lny8fyb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lny8fyb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:chevron-duo-up" /></template>

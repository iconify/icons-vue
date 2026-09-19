<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3dzk3lag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3dzk3lag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:heart-fill" /></template>

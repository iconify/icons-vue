<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u93049byl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u93049byl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-center-middle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-rj56b4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-rj56b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:jetpack" /></template>

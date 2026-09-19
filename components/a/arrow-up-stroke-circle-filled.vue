<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7kwzsb3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7kwzsb3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-up-stroke-circle-filled" /></template>

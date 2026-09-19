<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z67eqnb0d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z67eqnb0d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-circle-left-fill" /></template>

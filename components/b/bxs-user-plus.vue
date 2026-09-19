<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-z17_bzw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-z17_bzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-user-plus" /></template>

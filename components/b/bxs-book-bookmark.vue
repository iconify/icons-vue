<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgywio29h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cgywio29h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-book-bookmark" /></template>

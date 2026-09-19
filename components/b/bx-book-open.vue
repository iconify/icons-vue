<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_21izbtn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f_21izbtn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-book-open" /></template>

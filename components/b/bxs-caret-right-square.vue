<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3yk_lb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3yk_lb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-caret-right-square" /></template>

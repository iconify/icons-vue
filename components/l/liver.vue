<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqdxep41r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yqdxep41r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:liver" /></template>

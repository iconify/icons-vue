<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps7k2ibyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ps7k2ibyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:login-half-circle" /></template>

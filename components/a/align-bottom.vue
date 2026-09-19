<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt8glibwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt8glibwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:align-bottom" /></template>

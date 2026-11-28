<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s8i23yb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s8i23yb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:burger-heart" /></template>

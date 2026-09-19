<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dhqvjfb8b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="dhqvjfb8b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:cpanel" /></template>

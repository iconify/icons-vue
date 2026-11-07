<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_ic7jmnw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u_ic7jmnw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hearts-broken" /></template>

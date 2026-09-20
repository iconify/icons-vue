<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngd0dh-ag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ngd0dh-ag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:cc-diners-club" /></template>

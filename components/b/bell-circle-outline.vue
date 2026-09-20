<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c-xku8bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c-xku8bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bell-circle-outline" /></template>

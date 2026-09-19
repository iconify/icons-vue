<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m241b5b6o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m241b5b6o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:bolt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx7k5y9ht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx7k5y9ht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:home-star" /></template>

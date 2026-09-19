<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j29jv6bka.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j29jv6bka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:car-wash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6xlo2b-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6xlo2b-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:loader" /></template>

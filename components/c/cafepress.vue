<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cukae7boc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cukae7boc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:cafepress" /></template>

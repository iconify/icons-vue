<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m7x4gveff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7x4gveff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:address-book-outline" /></template>

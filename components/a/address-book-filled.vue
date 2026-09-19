<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/px8cn61kz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="px8cn61kz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:address-book-filled" /></template>

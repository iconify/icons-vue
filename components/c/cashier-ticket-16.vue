<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zw-kpqxcu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zw-kpqxcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cashier-ticket-16" /></template>

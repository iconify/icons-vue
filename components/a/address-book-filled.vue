<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qs3y2sk5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qs3y2sk5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:address-book-filled" /></template>

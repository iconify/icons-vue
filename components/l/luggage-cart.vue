<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt-eubb9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jt-eubb9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:luggage-cart" /></template>

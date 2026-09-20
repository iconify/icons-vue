<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9rsasb8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9rsasb8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:coffee-cup-2" /></template>

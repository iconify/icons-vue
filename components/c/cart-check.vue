<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8yady8wv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f8yady8wv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:cart-check" /></template>

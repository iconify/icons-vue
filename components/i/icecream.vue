<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sma23zlzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sma23zlzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:icecream" /></template>

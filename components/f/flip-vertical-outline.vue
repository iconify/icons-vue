<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6ht8njil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6ht8njil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:flip-vertical-outline" /></template>

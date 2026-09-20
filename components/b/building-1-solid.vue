<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8sarxb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="p8sarxb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:building-1-solid" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc-ttvbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jc-ttvbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:flag-alt-light" /></template>

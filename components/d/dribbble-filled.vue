<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cek003ruh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cek003ruh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:dribbble-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfh9rvbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sfh9rvbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-up-24" /></template>

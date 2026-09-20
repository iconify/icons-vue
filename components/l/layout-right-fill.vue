<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o86pnqbba.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o86pnqbba"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:layout-right-fill" /></template>

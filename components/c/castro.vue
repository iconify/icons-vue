<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/koupko15b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="koupko15b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:castro" /></template>

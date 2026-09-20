<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pt6qs7b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pt6qs7b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:discover" /></template>

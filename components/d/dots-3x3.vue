<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h5przi3uj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h5przi3uj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:dots-3x3" /></template>

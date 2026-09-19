<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_nb4-z7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_nb4-z7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:clock-1-filled" /></template>

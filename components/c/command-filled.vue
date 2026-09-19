<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v-sd6dlux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v-sd6dlux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:command-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n7pao0m-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="n7pao0m-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:background-color-accent" /></template>

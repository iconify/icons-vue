<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/di89s5fjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="di89s5fjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:laptop-alert" /></template>

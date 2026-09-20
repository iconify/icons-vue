<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c8nu23brh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c8nu23brh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:elipsis-double-v-alt" /></template>

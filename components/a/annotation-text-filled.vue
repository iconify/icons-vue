<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j4-1j-bxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4-1j-bxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:annotation-text-filled" /></template>

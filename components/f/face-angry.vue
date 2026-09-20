<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y571l1bgh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y571l1bgh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:face-angry" /></template>

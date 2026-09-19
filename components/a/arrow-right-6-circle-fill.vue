<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekn7hob8u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ekn7hob8u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:arrow-right-6-circle-fill" /></template>

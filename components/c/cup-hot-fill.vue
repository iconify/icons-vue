<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj3p56bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bj3p56bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:cup-hot-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js00izbwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js00izbwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:arrow-circle-up-solid" /></template>

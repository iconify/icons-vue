<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckrfwua4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":25,"height":24};
const content = `<path class="ckrfwua4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:hierarchy-1" /></template>

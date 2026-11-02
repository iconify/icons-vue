<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8ncn-msd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="z8ncn-msd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-up-left-20-solid" /></template>

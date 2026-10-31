<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi0yoom-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="xi0yoom-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:chevron-down-up-20-solid" /></template>

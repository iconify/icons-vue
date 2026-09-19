<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ru7ki0x_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ru7ki0x_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:logo-notion" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c88vd2bte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c88vd2bte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chevron-left-square-fill" /></template>

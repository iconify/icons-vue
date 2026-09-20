<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egtakmbsd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="egtakmbsd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:facebook-square" /></template>

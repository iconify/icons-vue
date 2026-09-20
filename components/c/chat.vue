<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjl5eprxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cjl5eprxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:chat" /></template>

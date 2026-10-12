<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o7kavpdpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="o7kavpdpi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:dots-vertical-20" /></template>

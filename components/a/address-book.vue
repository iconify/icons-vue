<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_0iyzb6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="j_0iyzb6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:address-book" /></template>

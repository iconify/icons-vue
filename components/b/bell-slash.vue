<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tevratbqa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tevratbqa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:bell-slash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqkjtsbhl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="jqkjtsbhl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:building" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv9j0ibxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="hv9j0ibxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:circle-letter-n" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipro3nb5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ipro3nb5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars-descending-align-left-arrow-down" /></template>

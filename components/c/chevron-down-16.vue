<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yz6c3ccrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="yz6c3ccrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:chevron-down-16" /></template>

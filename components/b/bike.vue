<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t743nvnom.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="t743nvnom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:bike" /></template>

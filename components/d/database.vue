<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op7podbxv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="op7podbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:database" /></template>

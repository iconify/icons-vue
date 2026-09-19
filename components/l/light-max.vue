<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/au28p2riu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="au28p2riu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:light-max" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_as61hbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="e_as61hbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:cut" /></template>

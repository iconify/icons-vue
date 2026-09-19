<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c69mprb9u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="c69mprb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:building" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vyci3rbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":109,"height":87};
const content = `<path class="vyci3rbny"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gozle" /></template>

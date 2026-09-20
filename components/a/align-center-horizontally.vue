<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekryhvxwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ekryhvxwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-center-horizontally" /></template>

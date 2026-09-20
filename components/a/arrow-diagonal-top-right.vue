<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da6d5ejeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="da6d5ejeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:arrow-diagonal-top-right" /></template>

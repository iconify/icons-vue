<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1s550b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v1s550b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:align-objects-bottom" /></template>

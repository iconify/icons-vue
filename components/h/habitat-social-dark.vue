<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/omrt5kbbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="omrt5kbbp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:habitat-social-dark" /></template>

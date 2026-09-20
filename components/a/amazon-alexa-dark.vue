<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya9w77bly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ya9w77bly"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:amazon-alexa-dark" /></template>

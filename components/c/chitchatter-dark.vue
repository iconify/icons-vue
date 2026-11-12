<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dqp834mog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="dqp834mog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:chitchatter-dark" /></template>

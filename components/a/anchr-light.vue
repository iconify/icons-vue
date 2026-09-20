<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jhiq11z0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jhiq11z0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anchr-light" /></template>

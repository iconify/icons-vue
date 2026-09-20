<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j73f_zbno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j73f_zbno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kopia-light" /></template>

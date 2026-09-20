<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_2y26brv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h_2y26brv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dfir-iris-light" /></template>

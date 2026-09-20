<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j88of6b-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j88of6b-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kontoj-light" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o0anb3hgy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o0anb3hgy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dropout-light" /></template>

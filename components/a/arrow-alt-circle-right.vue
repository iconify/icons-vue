<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl_f9mdkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xl_f9mdkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:arrow-alt-circle-right" /></template>

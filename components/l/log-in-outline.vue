<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gco9hqb4k.css';
import '../../css/o/ovur34-xv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="gco9hqb4k"/><path class="ovur34-xv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:log-in-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a47_abbvr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":432};
const content = `<path class="a47_abbvr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:group-work" /></template>

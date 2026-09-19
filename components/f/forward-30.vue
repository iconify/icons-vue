<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b__ieh4fk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":344,"height":432};
const content = `<path class="b__ieh4fk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:forward-30" /></template>

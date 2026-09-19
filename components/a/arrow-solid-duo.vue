<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ix_37863o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="ix_37863o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:arrow-solid-duo" /></template>

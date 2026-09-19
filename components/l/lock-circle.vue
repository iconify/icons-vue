<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/swz4mknri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="swz4mknri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lock-circle" /></template>

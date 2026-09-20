<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3r4d62pf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3r4d62pf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:arch-linux-dark" /></template>

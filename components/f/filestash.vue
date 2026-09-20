<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z4hx09p0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="z4hx09p0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filestash" /></template>

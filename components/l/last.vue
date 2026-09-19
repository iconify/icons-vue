<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z1qxa2w7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":464,"height":448};
const content = `<path class="z1qxa2w7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:last" /></template>

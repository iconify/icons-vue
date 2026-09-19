<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bloqio82m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="bloqio82m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:arrows-compress" /></template>

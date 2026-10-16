<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9i0psc1u.css';
import '../../css/d/d58o7tbnq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m9i0psc1u"/><path class="d58o7tbnq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:current-transformer-20" /></template>

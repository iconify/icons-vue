<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w5sf_o82m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="w5sf_o82m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-frown-open" /></template>

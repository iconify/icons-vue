<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwvjmvb6c.css';
import '../../css/o/ogd77sb1i.css';
import '../../css/g/g4-80-g_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zwvjmvb6c"/><path class="ogd77sb1i"/><path class="g4-80-g_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:beaver-habit-tracker" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud2t_6b-y.css';
import '../../css/h/hxggj4dhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="ud2t_6b-y"/><path class="hxggj4dhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="foundation:clock" /></template>

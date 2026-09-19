<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zvz700bpw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="zvz700bpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clock-in-fill-12" /></template>

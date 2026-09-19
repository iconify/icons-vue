<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w84vznkgo.css';
import '../../css/z/zah5plefr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="w84vznkgo"/><path class="zah5plefr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:ban-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2e05bcja.css';
import '../../css/v/vojou6b4q.css';
import '../../css/f/f4pvf8bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="d2e05bcja"/><path class="vojou6b4q"/><path class="f4pvf8bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:colota-light" /></template>

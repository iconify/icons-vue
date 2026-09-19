<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srbg1iv5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="srbg1iv5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-mdl2:add-notes" /></template>

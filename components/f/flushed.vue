<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikr30cc0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="ikr30cc0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:flushed" /></template>

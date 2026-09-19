<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/ja8d0ui8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ja8d0ui8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:face-frown" /></template>

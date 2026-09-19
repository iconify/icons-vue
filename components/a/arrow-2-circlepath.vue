<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rxi2q2i8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rxi2q2i8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:arrow-2-circlepath" /></template>

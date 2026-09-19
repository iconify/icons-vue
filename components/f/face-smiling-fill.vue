<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdy033b6z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="rdy033b6z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:face-smiling-fill" /></template>

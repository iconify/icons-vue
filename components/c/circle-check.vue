<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aljkuo7ct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="aljkuo7ct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-regular:circle-check" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rrwh4xbjw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="rrwh4xbjw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:copyright" /></template>

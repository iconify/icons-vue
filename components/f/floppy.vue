<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qk5carb5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="qk5carb5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:floppy" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixbb7_buq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ixbb7_buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:hearts" /></template>

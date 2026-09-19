<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w4cw9ebxc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="w4cw9ebxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:machine-wash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gna7bpbhe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gna7bpbhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:filter-filled" /></template>

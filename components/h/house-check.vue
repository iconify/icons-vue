<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q41rf3bpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q41rf3bpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:house-check" /></template>

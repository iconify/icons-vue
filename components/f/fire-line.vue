<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k-z8bpfqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k-z8bpfqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:fire-line" /></template>

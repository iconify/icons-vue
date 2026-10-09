<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fwtvv7bpf.css';
import '../../css/s/sxyqv-bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fwtvv7bpf"/><path class="sxyqv-bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-20-bold" /></template>

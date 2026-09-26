<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq8xlbpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ipq8xlbpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:icinga" /></template>

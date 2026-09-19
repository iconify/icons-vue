<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3mgh8bpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="q3mgh8bpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:contract-solid" /></template>

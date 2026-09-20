<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k3aek7nzy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k3aek7nzy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-down-s-line" /></template>

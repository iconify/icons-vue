<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kc8h-9bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kc8h-9bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:cluster-role-binding" /></template>

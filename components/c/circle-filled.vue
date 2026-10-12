<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz_ei8c0w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vz_ei8c0w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-filled" /></template>

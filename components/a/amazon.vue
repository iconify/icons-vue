<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/audx4-b0p.css';
import '../../css/p/pwd6rdbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="audx4-b0p"/><path class="pwd6rdbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:amazon" /></template>

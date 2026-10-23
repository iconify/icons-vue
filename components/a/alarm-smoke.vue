<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nbwj8s5ns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nbwj8s5ns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:alarm-smoke" /></template>

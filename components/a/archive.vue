<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vsd4puxnd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vsd4puxnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:archive" /></template>

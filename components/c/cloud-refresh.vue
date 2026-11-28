<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dgvyovbtr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgvyovbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:cloud-refresh" /></template>

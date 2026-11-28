<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nat0y94jm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nat0y94jm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:certificate-check" /></template>

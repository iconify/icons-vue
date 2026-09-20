<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uxvb0bbjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uxvb0bbjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:cloud-pin" /></template>

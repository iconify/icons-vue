<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x85ogmb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x85ogmb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clock-circle-outline" /></template>

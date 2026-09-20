<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/scyxcwbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scyxcwbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:lock-access-off" /></template>

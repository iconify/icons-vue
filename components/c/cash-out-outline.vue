<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doo982blv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="doo982blv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cash-out-outline" /></template>

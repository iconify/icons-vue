<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_yle3bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g_yle3bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:chevron-left-light" /></template>

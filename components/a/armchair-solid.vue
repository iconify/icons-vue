<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/if3j1ybfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="if3j1ybfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:armchair-solid" /></template>

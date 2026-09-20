<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-vm_3b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m-vm_3b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-shuffle" /></template>

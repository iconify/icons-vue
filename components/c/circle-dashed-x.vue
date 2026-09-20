<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szz_hddff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szz_hddff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:circle-dashed-x" /></template>

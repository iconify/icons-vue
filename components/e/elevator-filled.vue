<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smnhnb-ui.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smnhnb-ui"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:elevator-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a-k_fzbwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-k_fzbwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-ipad-horizontal-down" /></template>

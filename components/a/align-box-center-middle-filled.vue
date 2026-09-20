<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w8i_ynbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w8i_ynbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:align-box-center-middle-filled" /></template>

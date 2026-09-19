<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhxd_hbkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mhxd_hbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-small-down" /></template>

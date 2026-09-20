<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ps_dhvbjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps_dhvbjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gmx" /></template>

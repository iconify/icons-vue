<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uhuff7bhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uhuff7bhq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:currency-naira" /></template>

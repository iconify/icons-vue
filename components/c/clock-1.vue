<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k18y-k1ul.css';
import '../../css/v/vv34g_e8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k18y-k1ul"/><path class="vv34g_e8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:clock-1" /></template>

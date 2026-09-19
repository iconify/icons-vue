<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovu-g_vkt.css';
import '../../css/u/uivx-nb_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ovu-g_vkt"/><path class="uivx-nb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-minus" /></template>

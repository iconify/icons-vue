<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc4uod5nx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc4uod5nx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:facebook-gaming" /></template>

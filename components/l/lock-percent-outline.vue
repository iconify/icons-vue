<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zphlgebpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zphlgebpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:lock-percent-outline" /></template>

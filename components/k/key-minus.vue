<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqlqo2bgp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqlqo2bgp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:key-minus" /></template>

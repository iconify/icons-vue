<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/glqbyrb_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glqbyrb_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:ethernet-off" /></template>

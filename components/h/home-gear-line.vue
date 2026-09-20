<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pouzq5bzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pouzq5bzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:home-gear-line" /></template>

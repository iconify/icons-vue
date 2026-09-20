<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p4hav-1_r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p4hav-1_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:film-open-remove-outline" /></template>

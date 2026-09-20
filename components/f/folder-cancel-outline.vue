<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8_ilii_o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8_ilii_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:folder-cancel-outline" /></template>

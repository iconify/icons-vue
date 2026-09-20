<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soi53cr5t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soi53cr5t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-down-circle-outline" /></template>

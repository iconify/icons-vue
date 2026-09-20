<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyv4pt_zi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv4pt_zi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:clear-octagon-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpmie_b1t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cpmie_b1t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:chevron-up-box-outline" /></template>

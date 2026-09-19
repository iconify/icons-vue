<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mw_f-5rvp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mw_f-5rvp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:info-fill" /></template>

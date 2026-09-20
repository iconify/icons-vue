<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vximh_acq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vximh_acq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:citroen" /></template>

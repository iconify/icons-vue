<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/siglsi_5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="siglsi_5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-right-simple-line" /></template>

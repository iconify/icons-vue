<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gse3s6bul.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gse3s6bul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-adore-alt" /></template>

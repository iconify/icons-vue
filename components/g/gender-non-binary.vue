<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rp_tq7kpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rp_tq7kpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:gender-non-binary" /></template>

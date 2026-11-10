<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gga337kju.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gga337kju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="matita:gamma-capital" /></template>

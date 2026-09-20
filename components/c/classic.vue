<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s71qr6fcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path vector-effect="non-scaling-stroke" class="s71qr6fcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:classic" /></template>

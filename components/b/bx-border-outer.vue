<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lprujtblw.css';
import '../../css/m/mti94ib8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lprujtblw"/><path class="mti94ib8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-border-outer" /></template>

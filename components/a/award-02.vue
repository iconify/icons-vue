<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gupi_7glt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gupi_7glt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:award-02" /></template>

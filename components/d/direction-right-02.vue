<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i2fbyjfxa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i2fbyjfxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:direction-right-02" /></template>

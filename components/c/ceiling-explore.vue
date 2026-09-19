<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/ssc2c_b5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ssc2c_b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-explore" /></template>

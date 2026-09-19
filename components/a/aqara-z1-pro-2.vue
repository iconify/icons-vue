<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqe3nzz0g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqe3nzz0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:aqara-z1-pro-2" /></template>

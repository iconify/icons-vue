<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3lnl39gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u3lnl39gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:escalator-up" /></template>

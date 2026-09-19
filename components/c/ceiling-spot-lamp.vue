<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zpqaeac_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zpqaeac_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-spot-lamp" /></template>

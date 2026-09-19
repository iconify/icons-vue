<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k6oe_bc7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k6oe_bc7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:hino" /></template>

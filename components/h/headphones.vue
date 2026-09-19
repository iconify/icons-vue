<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb_657b7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb_657b7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:headphones" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euhjnp2jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euhjnp2jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:case-sensitive" /></template>

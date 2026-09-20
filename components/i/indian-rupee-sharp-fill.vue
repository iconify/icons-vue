<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqx5yqbct.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqx5yqbct"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:indian-rupee-sharp-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smc5l5zng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="smc5l5zng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:down-two-headed-fill" /></template>

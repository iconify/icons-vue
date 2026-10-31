<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amim8fd2o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="amim8fd2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-left-up-duotone-round" /></template>

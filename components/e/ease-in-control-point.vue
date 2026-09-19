<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tia-4zbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tia-4zbol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:ease-in-control-point" /></template>

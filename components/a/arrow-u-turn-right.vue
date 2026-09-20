<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eirz4gl8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eirz4gl8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-u-turn-right" /></template>

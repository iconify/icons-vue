<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sh-tc02bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sh-tc02bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:brand-slack" /></template>

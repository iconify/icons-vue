<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sny7_mbht.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sny7_mbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:baseball-fill" /></template>

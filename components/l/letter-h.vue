<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lq9ehbc9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq9ehbc9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:letter-h" /></template>

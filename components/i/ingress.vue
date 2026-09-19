<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iu898pi9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iu898pi9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:ingress" /></template>

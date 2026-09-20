<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pezpn2bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pezpn2bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-big-up-short-duotone" /></template>

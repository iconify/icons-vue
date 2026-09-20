<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pk09nrg1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pk09nrg1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:arrow-left-s-fill" /></template>

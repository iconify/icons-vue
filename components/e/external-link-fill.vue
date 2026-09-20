<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ht8hvn-4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ht8hvn-4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:external-link-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ibx1aab1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibx1aab1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:forward-end" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vfqal6bid.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vfqal6bid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:dollar-fill" /></template>

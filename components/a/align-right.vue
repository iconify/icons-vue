<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hf_48bbou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hf_48bbou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:align-right" /></template>

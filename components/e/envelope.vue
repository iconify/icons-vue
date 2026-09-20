<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij3qcmvxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij3qcmvxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:envelope" /></template>

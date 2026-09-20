<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f-z_lcbfv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f-z_lcbfv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:eth-line" /></template>

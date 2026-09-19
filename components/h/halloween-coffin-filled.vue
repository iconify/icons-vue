<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eqjs8aclk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eqjs8aclk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:halloween-coffin-filled" /></template>

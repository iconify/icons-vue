<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cw49yephw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw49yephw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:focus-m" /></template>

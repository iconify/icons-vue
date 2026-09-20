<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mrc3c7qlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mrc3c7qlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:corner-right-down" /></template>

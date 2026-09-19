<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mok1onfec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mok1onfec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:corner-down-right-outline" /></template>

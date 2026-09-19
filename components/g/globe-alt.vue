<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h20o60bso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h20o60bso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:globe-alt" /></template>

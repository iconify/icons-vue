<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2o7jubrf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z2o7jubrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:leg-24px" /></template>

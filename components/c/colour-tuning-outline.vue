<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eib-kokoe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="eib-kokoe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:colour-tuning-outline" /></template>

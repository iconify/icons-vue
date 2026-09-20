<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mh45oocjv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mh45oocjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-check-outline" /></template>

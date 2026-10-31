<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbqhn0p_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="cbqhn0p_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:heading-20-solid" /></template>

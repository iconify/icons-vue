<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tke0wbcic.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tke0wbcic"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:arrow-up-wide-narrow" /></template>

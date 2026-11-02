<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_owd-wra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="k_owd-wra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-curve-left-up-20-solid" /></template>

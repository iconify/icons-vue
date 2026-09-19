<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ecnejhb-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="ecnejhb-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:arrow-uturn-right-20-solid" /></template>

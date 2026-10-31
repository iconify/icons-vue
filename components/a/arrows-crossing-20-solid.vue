<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kn46_qbin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="kn46_qbin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrows-crossing-20-solid" /></template>

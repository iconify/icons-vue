<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ny-3uobra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ny-3uobra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:clipboard-16-solid" /></template>

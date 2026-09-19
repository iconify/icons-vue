<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nktbh_b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nktbh_b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:h2-16-solid" /></template>

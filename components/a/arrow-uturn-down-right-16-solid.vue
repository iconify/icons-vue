<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/diqex1eyy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="diqex1eyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="sidekickicons:arrow-uturn-down-right-16-solid" /></template>

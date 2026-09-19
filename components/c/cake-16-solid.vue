<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hpkw_81oa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hpkw_81oa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:cake-16-solid" /></template>

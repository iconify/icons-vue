<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eer9vgryz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="eer9vgryz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:cost-estimate-outline" /></template>

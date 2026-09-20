<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/azacryb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="azacryb7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-pediatrics" /></template>

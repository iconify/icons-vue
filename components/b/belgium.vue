<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkiwhgb7p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dkiwhgb7p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:belgium" /></template>

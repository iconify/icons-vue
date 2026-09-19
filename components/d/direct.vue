<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lckcu29tu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":100};
const content = `<path class="lckcu29tu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gis:direct" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cplin-bse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="cplin-bse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-no-access-outline" /></template>

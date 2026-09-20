<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dffe5p_ib.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="dffe5p_ib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fountain-from-ground" /></template>

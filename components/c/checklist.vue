<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ld_v0xb7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ld_v0xb7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:checklist" /></template>

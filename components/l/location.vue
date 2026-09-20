<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djm_3-bud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="djm_3-bud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:location" /></template>

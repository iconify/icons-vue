<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/as8m_2_xd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="as8m_2_xd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:file-plus-outline" /></template>

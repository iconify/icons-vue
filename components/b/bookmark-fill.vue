<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4m_vv5ce.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="x4m_vv5ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bookmark-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xowt0m_af.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="xowt0m_af"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:dialog-16" /></template>

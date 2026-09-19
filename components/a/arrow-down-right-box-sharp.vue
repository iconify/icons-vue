<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b918m_bmv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="b918m_bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:arrow-down-right-box-sharp" /></template>

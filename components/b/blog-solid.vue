<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7r80m_dn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w7r80m_dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:blog-solid" /></template>

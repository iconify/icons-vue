<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h17m_sbst.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":373,"height":512};
const content = `<path class="h17m_sbst"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:firebase" /></template>

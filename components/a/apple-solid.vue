<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqpkmbbws.css';
import '../../css/m/m_5z3sbiy.css';
import '../../css/g/g8175488f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="qqpkmbbws"/><path class="m_5z3sbiy"/><path class="g8175488f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:apple-solid" /></template>

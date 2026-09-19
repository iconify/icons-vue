<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hkxht-b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hkxht-b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hatena-bookmark" /></template>

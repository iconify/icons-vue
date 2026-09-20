<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vplm-nswe.css';
import '../../css/o/oplsioe0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":15};
const content = `<path class="vplm-nswe"/><path class="oplsioe0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:envelope-solid" /></template>

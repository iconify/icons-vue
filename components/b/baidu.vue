<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vuujibcul.css';
import '../../css/k/kzsue3_rw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vuujibcul"/><path class="kzsue3_rw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:baidu" /></template>

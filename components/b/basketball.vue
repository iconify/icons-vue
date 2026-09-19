<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wn3ror_qv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wn3ror_qv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ep:basketball" /></template>

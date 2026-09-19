<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/guan1wbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":896};
const content = `<path class="guan1wbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:galaxyalt" /></template>

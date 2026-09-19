<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b9kqm51ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":488,"height":496};
const content = `<path class="b9kqm51ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:brightness-5" /></template>

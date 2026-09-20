<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6m-zls6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":50,"height":50};
const content = `<path class="x6m-zls6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:lock" /></template>

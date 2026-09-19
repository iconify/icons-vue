<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wnmskeb_m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":832,"height":1024};
const content = `<path class="wnmskeb_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:hot" /></template>

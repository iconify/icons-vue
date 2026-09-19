<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bo-i9d5nt.css';
import '../../css/g/g5gysrbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bo-i9d5nt"/><path class="g5gysrbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:direction-curve-filled" /></template>

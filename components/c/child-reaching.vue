<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s34di-i6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="s34di-i6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:child-reaching" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkb-i8_jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fkb-i8_jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bytesize:github" /></template>

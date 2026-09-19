<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zzxfrybrb.css';
import '../../css/g/gxe7jmbor.css';
import '../../css/t/tp9_xo__k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zzxfrybrb"/><path class="gxe7jmbor"/><path class="tp9_xo__k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:calendar-add-alt" /></template>

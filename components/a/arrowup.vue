<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_554nb3a.css';
import '../../css/c/cxh3ar5_e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":9,"height":16};
const content = `<path class="f_554nb3a"/><path class="cxh3ar5_e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:arrowup" /></template>

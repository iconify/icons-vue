<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcs7_bcpt.css';
import '../../css/o/oq0kdrbfu.css';
import '../../css/b/bivc0_8ea.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bcs7_bcpt"/><path class="oq0kdrbfu"/><path class="bivc0_8ea"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="formkit:lira" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/ez1x61b2a.css';
import '../../css/z/zcrcylsxu.css';
import '../../css/g/gb_bkldvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="ez1x61b2a"/><circle class="zcrcylsxu"/><path class="gb_bkldvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:git-merge" /></template>

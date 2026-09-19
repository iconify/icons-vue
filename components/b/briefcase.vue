<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dlm8elbdv.css';
import '../../css/i/iuzbj5b6k.css';
import '../../css/d/dftf9rvck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dlm8elbdv"/><path class="iuzbj5b6k"/><circle class="dftf9rvck"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:briefcase" /></template>

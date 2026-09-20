<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/ljbdk7b8o.css';
import '../../css/r/rhi_p7bme.css';
import '../../css/c/c-umazbdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ljbdk7b8o"/><circle class="rhi_p7bme"/><circle class="c-umazbdf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:git-branch-line" /></template>

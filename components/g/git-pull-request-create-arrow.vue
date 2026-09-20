<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/l/llyo8-6yr.css';
import '../../css/y/yc9mclg0j.css';
import '../../css/s/s6dkgxb7c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><circle class="llyo8-6yr"/><path class="yc9mclg0j"/><path class="s6dkgxb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:git-pull-request-create-arrow" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d2kvgvbvc.css';
import '../../css/s/sw6vdtb6r.css';
import '../../css/d/dkl9z8v5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="sw6vdtb6r"/><path class="dkl9z8v5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:bamboo" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kdf4ztcgy.css';
import '../../css/s/s0tt-qp-f.css';
import '../../css/a/a44wmpb2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kdf4ztcgy"/><path class="s0tt-qp-f"/><path class="a44wmpb2v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:footprints-duotone" /></template>

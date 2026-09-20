<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/mc2zb0bvp.css';
import '../../css/z/z4pzsqb4a.css';
import '../../css/n/n7pyn85wa.css';
import '../../css/i/iy-t96bdf.css';
import '../../css/f/fhryxrb5j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><g class="mc2zb0bvp"><path class="z4pzsqb4a"/><path class="n7pyn85wa"/></g><path clip-rule="evenodd" class="iy-t96bdf"/><path clip-rule="evenodd" class="fhryxrb5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:git-diff-bold-duotone" /></template>

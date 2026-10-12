<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/e/evp8xsbel.css';
import '../../css/w/wu8w-7b0t.css';
import '../../css/l/lvwry-bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="evp8xsbel"/><path class="wu8w-7b0t"/><path class="lvwry-bxz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:box-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n6wq2qewp.css';
import '../../css/v/v1db-bbbt.css';
import '../../css/a/aaralt-wc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n6wq2qewp"/><path class="v1db-bbbt"/><path class="aaralt-wc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-helping-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5u34vbpt.css';
import '../../css/i/iwa9eupgf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="o5u34vbpt"/><path class="iwa9eupgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gallery-add-bold-duotone" /></template>

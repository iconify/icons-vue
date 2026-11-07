<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtplmt03a.css';
import '../../css/g/gt-p5sx5s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mtplmt03a"/><path clip-rule="evenodd" class="gt-p5sx5s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:copy-minus-bold-duotone" /></template>

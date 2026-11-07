<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dm03gzbnp.css';
import '../../css/c/cdweb5b1o.css';
import '../../css/m/mtbem4pdc.css';
import '../../css/f/fqm-9ybin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dm03gzbnp"/><path class="cdweb5b1o"/><path class="mtbem4pdc"/><path class="fqm-9ybin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:download-twice-square-bold-duotone" /></template>

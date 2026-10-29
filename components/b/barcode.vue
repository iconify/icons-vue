<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-wcl9bei.css';
import '../../css/a/aranxlsbw.css';
import '../../css/o/of4wwqxia.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-wcl9bei"/><path class="aranxlsbw"/><path class="of4wwqxia"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:barcode" /></template>

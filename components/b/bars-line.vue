<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-3-isbfd.css';
import '../../css/c/c6irxih5p.css';
import '../../css/z/zyoh9lzam.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="b-3-isbfd clr-i-outline clr-i-outline-path-1"/><path class="c6irxih5p clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 zyoh9lzam"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:bars-line" /></template>

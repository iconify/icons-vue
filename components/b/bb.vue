<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/a/avvfdb35i.css';
import '../../css/b/bgs-3wb5e.css';
import '../../css/z/zrjmoujkm.css';
import '../../css/k/k15qmubyq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="avvfdb35i"/><path class="bgs-3wb5e"/><path class="zrjmoujkm"/><path class="k15qmubyq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:bb" /></template>

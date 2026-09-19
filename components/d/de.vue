<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/y/yzfkwyb_b.css';
import '../../css/c/cu3su9ffu.css';
import '../../css/o/o1sk4_0cf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="yzfkwyb_b"/><path class="cu3su9ffu"/><path class="o1sk4_0cf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:de" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrj6p8qat.css';
import '../../css/o/o_zfirn9i.css';
import '../../css/o/ot8yzyb7e.css';
import '../../css/y/yoyle7z3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o_zfirn9i"/><path class="ot8yzyb7e"/><circle class="yoyle7z3v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:book-image" /></template>

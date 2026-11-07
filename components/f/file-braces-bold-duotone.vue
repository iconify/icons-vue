<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jav_zgbsf.css';
import '../../css/l/l3981gogh.css';
import '../../css/u/ubn_7xb7s.css';
import '../../css/o/oj6gwrmjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jav_zgbsf"/><path class="l3981gogh"/><path class="ubn_7xb7s"/><path clip-rule="evenodd" class="oj6gwrmjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:file-braces-bold-duotone" /></template>

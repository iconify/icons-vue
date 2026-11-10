<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/h/hm0z84mqz.css';
import '../../css/i/im-u2lvxf.css';
import '../../css/r/rzklukbol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="hm0z84mqz"/><path class="im-u2lvxf"/><path class="rzklukbol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-plus-duotone" /></template>

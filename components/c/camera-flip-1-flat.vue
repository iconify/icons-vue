<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/i/i4xtvfb6s.css';
import '../../css/d/dn-fkoz4z.css';
import '../../css/j/jz3sd-cwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="i4xtvfb6s"/><path class="dn-fkoz4z"/><path class="jz3sd-cwn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:camera-flip-1-flat" /></template>

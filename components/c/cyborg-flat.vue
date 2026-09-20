<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi12bsetm.css';
import '../../css/m/mo0jvlb2k.css';
import '../../css/z/zdil9-bok.css';
import '../../css/m/mhxwe-b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="mo0jvlb2k"/><path class="zdil9-bok"/><path class="mhxwe-b9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-color:cyborg-flat" /></template>

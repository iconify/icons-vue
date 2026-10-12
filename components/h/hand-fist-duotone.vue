<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/u/ur9kflbuq.css';
import '../../css/l/lbfwef4od.css';
import '../../css/j/jvmrv6zbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ur9kflbuq"/><path class="lbfwef4od"/><path class="jvmrv6zbn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:hand-fist-duotone" /></template>

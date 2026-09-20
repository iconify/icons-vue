<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rx164ab-f.css';
import '../../css/x/xc8prln3k.css';
import '../../css/o/oswetkbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="rx164ab-f"/><path class="xc8prln3k"/><path class="oswetkbup"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:globe-filled" /></template>

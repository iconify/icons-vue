<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/m/mq7zwiqhb.css';
import '../../css/j/jl73e1lrn.css';
import '../../css/i/im8flh3ra.css';
import '../../css/y/yij8ymbvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="mq7zwiqhb wm-shadow"/><path class="jl73e1lrn wm-shadow"/><path class="im8flh3ra"/><path class="yij8ymbvm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:external-link" /></template>

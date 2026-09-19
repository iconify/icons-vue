<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/h/hrq90hfel.css';
import '../../css/k/karhh3sue.css';
import '../../css/y/ydwm7ozks.css';
import '../../css/r/rc1-c96xu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="s9cl3zbei"><circle class="hrq90hfel"/><path class="karhh3sue"/><path class="ydwm7ozks"/><path class="rc1-c96xu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:delete-three" /></template>

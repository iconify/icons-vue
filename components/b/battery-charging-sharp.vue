<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u7q87o6mu.css';
import '../../css/m/mnrm0dbsd.css';
import '../../css/d/dir4mc3_p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="u7q87o6mu"/><path class="mnrm0dbsd"/><path class="dir4mc3_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:battery-charging-sharp" /></template>

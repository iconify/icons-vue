<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p51s5nbfp.css';
import '../../css/v/vdipyz_so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="p51s5nbfp"/><path class="vdipyz_so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:google-analytics" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yk1mbvbfk.css';
import '../../css/b/b4-fwcc_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":63,"height":64};
const content = `<path class="yk1mbvbfk"/><path class="b4-fwcc_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-imaging-alternative-mri" /></template>

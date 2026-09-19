<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/spat6qbum.css';
import '../../css/g/ga5ow5xim.css';
import '../../css/x/x8r3bo3uc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="spat6qbum"/><path class="ga5ow5xim"/><path class="x8r3bo3uc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ibm-cloud-pak-business-automation" /></template>

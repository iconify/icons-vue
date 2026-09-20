<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm2q14o2t.css';
import '../../css/c/czb5--bqu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qm2q14o2t"/><path class="czb5--bqu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:contao" /></template>

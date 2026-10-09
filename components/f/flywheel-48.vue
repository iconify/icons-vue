<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqul4gkqk.css';
import '../../css/u/u7bozsa8i.css';
import '../../css/t/tkxry7wol.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zqul4gkqk"/><path class="u7bozsa8i"/><path class="tkxry7wol"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:flywheel-48" /></template>

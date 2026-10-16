<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/of_ts022v.css';
import '../../css/c/cj1nlzlda.css';
import '../../css/t/tjxajkbik.css';
import '../../css/j/j-iq2zbqg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="of_ts022v"/><path class="cj1nlzlda"/><path class="tjxajkbik"/><path class="j-iq2zbqg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-cycle-48" /></template>

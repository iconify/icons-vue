<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emlsrnxct.css';
import '../../css/w/w80nymbio.css';
import '../../css/i/io7sfnrdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="emlsrnxct"/><path class="w80nymbio"/><path class="io7sfnrdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:factory-emissions-20" /></template>

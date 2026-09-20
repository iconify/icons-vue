<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k5uvpgbez.css';
import '../../css/h/h_pt1abna.css';
import '../../css/h/hlibxwb-i.css';
import '../../css/e/e4zfowz9r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="k5uvpgbez"/><path class="h_pt1abna"/><path class="hlibxwb-i"/><path class="e4zfowz9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:libra" /></template>

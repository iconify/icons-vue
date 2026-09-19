<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pc2-_9bsz.css';
import '../../css/h/htsp7iemw.css';
import '../../css/g/geee6pspy.css';
import '../../css/c/c9czsybcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pc2-_9bsz"/><path class="htsp7iemw"/><path class="geee6pspy"/><path class="c9czsybcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-loop-strong" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmys1lirk.css';
import '../../css/l/lfy066c5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="lmys1lirk"/><path class="lfy066c5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:down-right-arrow" /></template>

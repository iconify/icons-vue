<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kyv-fhcut.css';
import '../../css/j/jy-ypz30g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyv-fhcut"/><path class="jy-ypz30g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-dryer" /></template>

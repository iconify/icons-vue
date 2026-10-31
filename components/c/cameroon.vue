<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-4cv_cxz.css';
import '../../css/v/v5r_03b1l.css';
import '../../css/r/rsodfxbti.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="h-4cv_cxz"/><path class="v5r_03b1l"/><path class="rsodfxbti"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:cameroon" /></template>

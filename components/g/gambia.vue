<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt4xytbyt.css';
import '../../css/r/r0k-ltjjw.css';
import '../../css/d/dz--kkbng.css';
import '../../css/k/k40zmxb3r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="tt4xytbyt"/><path class="r0k-ltjjw"/><path class="dz--kkbng"/><path class="k40zmxb3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:gambia" /></template>

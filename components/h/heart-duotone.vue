<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvnf7s1_x.css';
import '../../css/r/r2uj8dq1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvnf7s1_x"/><path class="r2uj8dq1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:heart-duotone" /></template>

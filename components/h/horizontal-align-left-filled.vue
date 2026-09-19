<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4tqe28pg.css';
import '../../css/d/dy_9shbsz.css';
import '../../css/y/yr6e5mbng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4tqe28pg"/><rect class="dy_9shbsz"/><rect class="yr6e5mbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-align-left-filled" /></template>

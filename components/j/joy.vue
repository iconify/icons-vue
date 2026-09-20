<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhd2f7u1l.css';
import '../../css/d/dcvw64xgv.css';
import '../../css/s/scxamt7eq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhd2f7u1l"/><path class="dcvw64xgv"/><path class="scxamt7eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:joy" /></template>

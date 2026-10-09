<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic7c4od3i.css';
import '../../css/a/akg87ebjx.css';
import '../../css/u/u4as3jk4r.css';
import '../../css/t/t2b-glb-m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ic7c4od3i"/><path class="akg87ebjx"/><path class="u4as3jk4r"/><path class="t2b-glb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:carbon-storage-20" /></template>

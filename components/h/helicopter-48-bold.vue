<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tomb__uya.css';
import '../../css/v/vd19ejbdy.css';
import '../../css/f/fs7__xl7e.css';
import '../../css/x/xw6ho4bxz.css';
import '../../css/v/vq3mlfbcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tomb__uya"/><path class="vd19ejbdy"/><path class="fs7__xl7e"/><path class="xw6ho4bxz"/><path class="vq3mlfbcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:helicopter-48-bold" /></template>

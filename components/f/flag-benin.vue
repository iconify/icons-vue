<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dur0b2p3t.css';
import '../../css/h/h8ttso15c.css';
import '../../css/r/rmslx6b5x.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="dur0b2p3t"/><path class="h8ttso15c"/><path class="rmslx6b5x"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-benin" /></template>

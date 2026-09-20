<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rn8ox-tri.css';
import '../../css/d/dqshq-b0e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="rn8ox-tri"/><path class="dqshq-b0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:easy-redmine" /></template>

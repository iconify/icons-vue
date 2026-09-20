<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1q08elin.css';
import '../../css/l/lqso_0biw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="r1q08elin"/><path class="lqso_0biw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:initiative-project-management-light" /></template>

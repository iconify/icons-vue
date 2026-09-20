<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq601vtik.css';
import '../../css/o/om7fi_u-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mq601vtik"/><path class="om7fi_u-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:glink" /></template>

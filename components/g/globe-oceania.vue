<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ycfta7yog.css';
import '../../css/l/lwrzs1b5v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ycfta7yog"/><path class="lwrzs1b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:globe-oceania" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x3kws5b8f.css';
import '../../css/r/rqm0q0u6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x3kws5b8f"/><path class="rqm0q0u6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:dam-7-filled" /></template>

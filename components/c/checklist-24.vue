<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lw5jslsmt.css';
import '../../css/l/l5ucbdcah.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw5jslsmt"/><path class="l5ucbdcah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:checklist-24" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gk1iewbti.css';
import '../../css/q/ql1midcyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gk1iewbti"/><path class="ql1midcyw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:globe-off-filled" /></template>

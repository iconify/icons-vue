<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cqha-5bom.css';
import '../../css/j/jsdqiibqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cqha-5bom"/><path class="jsdqiibqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-up-from-line-bold-duotone" /></template>

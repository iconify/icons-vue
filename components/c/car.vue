<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oyor_thbf.css';
import '../../css/p/psi0ttbxr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<circle class="oyor_thbf"/><path class="psi0ttbxr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:car" /></template>

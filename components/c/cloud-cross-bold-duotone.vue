<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg6z1ub6a.css';
import '../../css/j/j3-vhnb6i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6z1ub6a"/><path clip-rule="evenodd" class="j3-vhnb6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cloud-cross-bold-duotone" /></template>

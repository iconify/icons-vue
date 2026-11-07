<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mp8cnibtf.css';
import '../../css/g/g95h_vbdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="mp8cnibtf"/><path class="g95h_vbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:arrow-right-up-bold-duotone" /></template>

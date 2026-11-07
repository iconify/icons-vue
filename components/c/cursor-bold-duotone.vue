<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tzpfhccmd.css';
import '../../css/y/yg46shszw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tzpfhccmd"/><path class="yg46shszw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:cursor-bold-duotone" /></template>

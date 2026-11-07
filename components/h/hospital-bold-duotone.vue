<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqx3r_ngw.css';
import '../../css/o/o3p-r8q4o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qqx3r_ngw"/><path class="o3p-r8q4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:hospital-bold-duotone" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz2ub5bko.css';
import '../../css/h/hazygbbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vz2ub5bko"/><path class="hazygbbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-with-files-bold" /></template>

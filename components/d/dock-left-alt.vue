<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emos5l7br.css';
import '../../css/d/dn42tbchj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emos5l7br"/><path class="dn42tbchj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-left-alt" /></template>

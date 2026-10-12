<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md_3dldtk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="md_3dldtk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:live-off" /></template>

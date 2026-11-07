<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pv_hji6de.css';
import '../../css/o/ovnacibyj.css';
import '../../css/h/h4_-fn3-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pv_hji6de"/><path class="ovnacibyj"/><path class="h4_-fn3-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:link-square-bold-duotone" /></template>

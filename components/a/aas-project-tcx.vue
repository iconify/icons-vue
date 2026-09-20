<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lcemhlb5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcemhlb5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:aas-project-tcx" /></template>

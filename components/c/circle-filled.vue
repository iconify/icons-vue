<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h45zs_cpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h45zs_cpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:circle-filled" /></template>

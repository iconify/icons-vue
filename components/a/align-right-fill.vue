<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lajo8c0zh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lajo8c0zh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:align-right-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dq_v0_2ro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dq_v0_2ro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:code-muted-duotone" /></template>

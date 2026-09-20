<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya01r5b4e.css';
import '../../css/t/t_5-mteix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya01r5b4e"/><path clip-rule="evenodd" class="t_5-mteix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:iris" /></template>

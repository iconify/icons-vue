<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/al0fg069v.css';
import '../../css/x/x1_ejpb7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="al0fg069v"/><path class="x1_ejpb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:hjson" /></template>

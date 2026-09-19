<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qya3aihwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qya3aihwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-remtang" /></template>

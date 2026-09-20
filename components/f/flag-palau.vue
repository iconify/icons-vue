<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vymljlban.css';
import '../../css/c/c8er-hbku.css';
import '../../css/q/qy525jbwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="vymljlban"/><circle class="c8er-hbku"/><path class="qy525jbwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:flag-palau" /></template>

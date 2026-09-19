<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2x54nbfw.css';
import '../../css/c/c41bz1boa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":480};
const content = `<path class="l2x54nbfw"/><circle class="c41bz1boa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:bd-4x3" /></template>

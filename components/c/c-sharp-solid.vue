<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f8p6y7blj.css';
import '../../css/m/ma5_rlb1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="f8p6y7blj"/><path clip-rule="evenodd" class="ma5_rlb1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:c-sharp-solid" /></template>

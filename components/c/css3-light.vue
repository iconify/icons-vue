<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqn4acquj.css';
import '../../css/e/eyi6n2idh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jqn4acquj"/><path class="eyi6n2idh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:css3-light" /></template>

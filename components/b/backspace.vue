<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oanleacgm.css';
import '../../css/o/opsmh7beo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="oanleacgm"/><path class="opsmh7beo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:backspace" /></template>

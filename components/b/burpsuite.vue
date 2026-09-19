<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g37freb4x.css';
import '../../css/c/ck8n3ib1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g37freb4x"/><path class="ck8n3ib1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:burpsuite" /></template>

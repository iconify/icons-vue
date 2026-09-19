<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qr4xlubum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qr4xlubum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:hoppscotch" /></template>

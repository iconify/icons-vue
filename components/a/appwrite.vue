<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/macbe7bdm.css';
import '../../css/l/lw3w-bciy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="macbe7bdm"/><path class="lw3w-bciy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:appwrite" /></template>

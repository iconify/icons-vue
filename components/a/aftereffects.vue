<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n0cuc_bpo.css';
import '../../css/h/h-ofk3o6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="n0cuc_bpo"/><path class="h-ofk3o6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:aftereffects" /></template>

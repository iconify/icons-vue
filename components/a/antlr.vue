<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ynxabotvb.css';
import '../../css/n/nk5kckb1g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ynxabotvb"/><path class="nk5kckb1g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:antlr" /></template>

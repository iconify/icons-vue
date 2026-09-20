<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qhfxrxiwf.css';
import '../../css/o/o_zlcrb8j.css';
import '../../css/z/z75nfbbdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<rect class="qhfxrxiwf"/><rect class="o_zlcrb8j"/><path class="z75nfbbdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:android" /></template>

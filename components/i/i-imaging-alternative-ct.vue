<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4porcctd.css';
import '../../css/e/egn_lcc1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g4porcctd"/><path class="egn_lcc1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-imaging-alternative-ct" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrsmjybvs.css';
import '../../css/t/tc0ligbel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrsmjybvs"/><path class="tc0ligbel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bnx" /></template>

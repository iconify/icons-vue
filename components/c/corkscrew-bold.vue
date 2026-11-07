<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rzj2_rlmw.css';
import '../../css/r/r641g4blr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rzj2_rlmw"/><path class="r641g4blr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:corkscrew-bold" /></template>

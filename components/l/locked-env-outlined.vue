<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rlzjfpbie.css';
import '../../css/w/wode1sbbf.css';
import '../../css/t/t3m92_bgb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlzjfpbie"/><path class="wode1sbbf"/><path class="t3m92_bgb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:locked-env-outlined" /></template>

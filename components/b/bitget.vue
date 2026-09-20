<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf--c0vyf.css';
import '../../css/z/z72r2ab5f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf--c0vyf"/><path class="z72r2ab5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bitget" /></template>

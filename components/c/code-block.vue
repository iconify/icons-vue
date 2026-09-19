<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz_8dhp3p.css';
import '../../css/v/v85x6e0bv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cz_8dhp3p"/><path class="v85x6e0bv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:code-block" /></template>

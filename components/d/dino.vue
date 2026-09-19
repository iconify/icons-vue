<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ln2z1rd5k.css';
import '../../css/o/osq-njbwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ln2z1rd5k"/><path class="osq-njbwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dino" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqs0f2fsr.css';
import '../../css/u/uq4zqzbch.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqs0f2fsr"/><path class="uq4zqzbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:border-inner" /></template>

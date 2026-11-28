<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyvcic_1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyvcic_1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:log-out-solid" /></template>

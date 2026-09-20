<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dza_qqxed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dza_qqxed"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:blogger-alt" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3_cy_qfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3_cy_qfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:eject-line" /></template>

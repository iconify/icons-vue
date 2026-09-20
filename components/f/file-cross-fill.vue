<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qm7m2abwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qm7m2abwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:file-cross-fill" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yfz3w9lrl.css';
import '../../css/l/ltep8mzcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="yfz3w9lrl"/><path class="ltep8mzcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:female" /></template>

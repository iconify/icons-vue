<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaa98ibfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="qaa98ibfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:circle-fill" /></template>

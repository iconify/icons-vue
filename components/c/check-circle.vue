<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neifvedcl.css';
import '../../css/e/etgavr0mg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neifvedcl"/><path class="etgavr0mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:check-circle" /></template>

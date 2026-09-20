<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-a_st0ek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-a_st0ek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:compress" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hugpkvbpv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hugpkvbpv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:castle-line" /></template>

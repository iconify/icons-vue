<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7qgn3bpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7qgn3bpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:creo" /></template>

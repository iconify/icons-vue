<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qtwqv5btz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qtwqv5btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:binary-solid" /></template>

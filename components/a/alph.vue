<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-am5se9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q-am5se9g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:alph" /></template>

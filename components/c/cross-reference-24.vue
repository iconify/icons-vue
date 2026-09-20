<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cjwnci-_l.css';
import '../../css/i/izsswccel.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cjwnci-_l"/><path class="izsswccel"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:cross-reference-24" /></template>

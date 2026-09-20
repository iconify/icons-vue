<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2n5zgbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z2n5zgbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:arrow-left-24" /></template>

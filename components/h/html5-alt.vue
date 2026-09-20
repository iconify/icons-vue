<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dd6l-0h0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dd6l-0h0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:html5-alt" /></template>

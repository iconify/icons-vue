<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kghif2ogu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kghif2ogu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:historic-shield-alt" /></template>

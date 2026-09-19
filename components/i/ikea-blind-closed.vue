<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k0hg82hni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k0hg82hni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-blind-closed" /></template>

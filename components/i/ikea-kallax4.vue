<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ers4h5bnl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ers4h5bnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ikea-kallax4" /></template>

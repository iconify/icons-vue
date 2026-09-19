<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbsyws46y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbsyws46y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:apple" /></template>

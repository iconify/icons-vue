<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp7k9_mku.css';
import '../../css/b/btu4zi_dc.css';
import '../../css/x/xcbtxr5ut.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yp7k9_mku"/><circle class="btu4zi_dc"/><path class="xcbtxr5ut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="circum:circle-question" /></template>

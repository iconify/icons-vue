<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcho26b_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vcho26b_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:clojure" /></template>

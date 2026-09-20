<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc50j-b_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc50j-b_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:grid5-filled" /></template>

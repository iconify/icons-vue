<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqqj_ob1e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iqqj_ob1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:gplv3" /></template>

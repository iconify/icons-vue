<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tpk4ihbzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tpk4ihbzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:bolt-slash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlcinebpq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qlcinebpq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:dice-d10-solid" /></template>

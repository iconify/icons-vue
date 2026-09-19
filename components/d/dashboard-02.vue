<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqg2si9cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qqg2si9cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:dashboard-02" /></template>

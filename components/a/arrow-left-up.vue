<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epr8oqldn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="epr8oqldn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-left-up" /></template>

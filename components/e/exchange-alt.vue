<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j702q-6qp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j702q-6qp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:exchange-alt" /></template>

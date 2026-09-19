<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inl2g9ceq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inl2g9ceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ci:keyboard" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oc56eqbnu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oc56eqbnu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:arrow-down-outline" /></template>

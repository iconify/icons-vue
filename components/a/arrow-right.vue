<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5a_1ab3h.css';
import '../../css/k/kdyg1ukjd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5a_1ab3h"/><path class="kdyg1ukjd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:arrow-right" /></template>

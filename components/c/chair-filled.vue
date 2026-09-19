<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ub-8msbxg.css';
import '../../css/u/u68we71_t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<rect class="ub-8msbxg"/><path class="u68we71_t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:chair-filled" /></template>

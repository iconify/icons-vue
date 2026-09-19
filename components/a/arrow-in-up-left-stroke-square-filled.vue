<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_-go266m.css';
import '../../css/q/q-jo2hc6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_-go266m"/><path class="q-jo2hc6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-up-left-stroke-square-filled" /></template>

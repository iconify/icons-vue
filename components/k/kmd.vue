<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tfy-5hqci.css';
import '../../css/x/x0u_kcboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tfy-5hqci"/><path class="x0u_kcboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kmd" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5el33zrv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5el33zrv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-lab:iron-off" /></template>

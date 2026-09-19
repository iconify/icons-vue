<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/szni6i3td.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szni6i3td"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:dialpad" /></template>

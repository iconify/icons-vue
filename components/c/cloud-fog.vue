<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/two12q6ud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="two12q6ud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:cloud-fog" /></template>

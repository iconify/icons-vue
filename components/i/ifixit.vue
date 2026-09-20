<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/ts5xhubqm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ts5xhubqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:ifixit" /></template>

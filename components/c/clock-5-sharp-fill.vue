<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dbs1q3kot.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dbs1q3kot"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-5-sharp-fill" /></template>

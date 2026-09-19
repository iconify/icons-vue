<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/laoledbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="laoledbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:defibrillator-24px" /></template>

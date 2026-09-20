<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m_exp8gqp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="m_exp8gqp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:hand-grenade" /></template>

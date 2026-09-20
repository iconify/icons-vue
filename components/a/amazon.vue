<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up97d7kqc.css';
import '../../css/o/or2m_gb2c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up97d7kqc"/><path class="or2m_gb2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:amazon" /></template>

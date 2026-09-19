<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g52m_vhun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g52m_vhun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:clinical-f-24px" /></template>

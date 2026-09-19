<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdltmv-sf.css';
import '../../css/g/gl2m_3bhg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdltmv-sf"/><path class="gl2m_3bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:calendar-cog-filled" /></template>

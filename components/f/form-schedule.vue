<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqldvs1fs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jqldvs1fs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-schedule" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ep71wbcll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ep71wbcll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-upload" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv48bd8ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv48bd8ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-close" /></template>

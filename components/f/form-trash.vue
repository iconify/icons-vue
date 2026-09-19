<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lvg8s9_1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lvg8s9_1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-trash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-wq09z1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-wq09z1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-edit" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/apc9u9b0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="apc9u9b0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-view" /></template>

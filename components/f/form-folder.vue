<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bxrd8lbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxrd8lbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-folder" /></template>

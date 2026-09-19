<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn5eqbb4c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn5eqbb4c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:form-next-link" /></template>

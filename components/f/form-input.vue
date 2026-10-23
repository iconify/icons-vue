<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myfxhn23z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="myfxhn23z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wordpress:form-input" /></template>

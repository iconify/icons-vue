<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jqvx9zbwv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jqvx9zbwv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-kidney" /></template>

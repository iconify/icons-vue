<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rsqlehbiw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rsqlehbiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:asterisk" /></template>

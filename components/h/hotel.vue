<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7lgo4b-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x7lgo4b-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:hotel" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/inz6rjbmn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="inz6rjbmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chupa-chups" /></template>

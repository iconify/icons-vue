<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ngda-7gsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ngda-7gsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:keep-a-changelog" /></template>

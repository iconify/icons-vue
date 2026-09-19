<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pipk6ibqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pipk6ibqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:link" /></template>

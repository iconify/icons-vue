<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lt0e6jbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt0e6jbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:bulma" /></template>

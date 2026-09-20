<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zabn7ccvz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zabn7ccvz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fusionauth" /></template>

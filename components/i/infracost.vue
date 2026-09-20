<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghnfzw7so.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghnfzw7so"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:infracost" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jc09--5dt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="jc09--5dt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:file-woff" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9vlgipnf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9vlgipnf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:compare" /></template>

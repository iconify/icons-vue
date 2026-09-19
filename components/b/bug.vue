<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wr197o85d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wr197o85d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="grommet-icons:bug" /></template>

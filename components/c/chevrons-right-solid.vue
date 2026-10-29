<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6ve2ebwf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6ve2ebwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:chevrons-right-solid" /></template>

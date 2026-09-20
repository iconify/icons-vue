<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mgrbkpb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgrbkpb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:file-minus-corner" /></template>

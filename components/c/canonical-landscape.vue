<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejl9-ctos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ejl9-ctos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:canonical-landscape" /></template>

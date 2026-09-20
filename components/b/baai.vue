<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ovvqqccal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ovvqqccal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:baai" /></template>

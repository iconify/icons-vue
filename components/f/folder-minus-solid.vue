<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/by87w4spn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="by87w4spn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:folder-minus-solid" /></template>

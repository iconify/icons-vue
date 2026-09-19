<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mbpsy19-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="mbpsy19-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:folder" /></template>

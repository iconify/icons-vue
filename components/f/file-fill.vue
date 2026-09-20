<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6c_nwb3c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g6c_nwb3c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:file-fill" /></template>

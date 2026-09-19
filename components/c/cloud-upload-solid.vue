<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/meyqr7u7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="meyqr7u7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:cloud-upload-solid" /></template>

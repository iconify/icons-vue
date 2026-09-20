<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsrb3dbkn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsrb3dbkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:download-stack-solid" /></template>

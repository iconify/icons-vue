<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zho0a0box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zho0a0box"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:devices-alt-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sge51zbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sge51zbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:globe-alt-02-filled" /></template>

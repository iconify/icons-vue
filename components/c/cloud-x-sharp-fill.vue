<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wv-d25bbn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wv-d25bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cloud-x-sharp-fill" /></template>

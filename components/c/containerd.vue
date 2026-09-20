<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlfmv5tdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlfmv5tdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:containerd" /></template>

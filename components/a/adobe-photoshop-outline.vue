<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sw1yyfbkx.css';
import '../../css/c/czjy8k8hn.css';
import '../../css/d/daxtkab1a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="sw1yyfbkx"/><path class="czjy8k8hn"/><path clip-rule="evenodd" class="daxtkab1a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="basil:adobe-photoshop-outline" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvz9emb-n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jvz9emb-n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:letter-m-octagon-solid" /></template>

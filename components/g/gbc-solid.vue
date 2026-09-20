<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/de42aeb0l.css';
import '../../css/y/yfn2vsbhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="de42aeb0l"/><path clip-rule="evenodd" class="yfn2vsbhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:gbc-solid" /></template>

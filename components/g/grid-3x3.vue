<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmfmj4bzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmfmj4bzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:grid-3x3" /></template>

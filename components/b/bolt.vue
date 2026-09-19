<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf8-odb2n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf8-odb2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gg:bolt" /></template>

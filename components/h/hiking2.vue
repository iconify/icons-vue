<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb532wbov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb532wbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hiking2" /></template>

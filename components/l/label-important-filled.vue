<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/loo4nhxhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="loo4nhxhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:label-important-filled" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xwvy_shai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xwvy_shai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:hal" /></template>

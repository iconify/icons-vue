<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxrhbebwx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="zxrhbebwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:html5-outline" /></template>

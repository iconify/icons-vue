<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pip8p3bjk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":480};
const content = `<path class="pip8p3bjk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:car-wash" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d09-d0b7r.css';
import '../../css/l/l44o3se9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d09-d0b7r"/><path class="l44o3se9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:ball-throw" /></template>

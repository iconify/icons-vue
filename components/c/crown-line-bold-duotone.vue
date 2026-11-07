<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq8bxxi9p.css';
import '../../css/z/zyfh3yufc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zq8bxxi9p"/><path class="zyfh3yufc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crown-line-bold-duotone" /></template>

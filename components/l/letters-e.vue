<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lrd0ecotk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lrd0ecotk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:letters-e" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blb603pzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="blb603pzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:arrows-maximize" /></template>

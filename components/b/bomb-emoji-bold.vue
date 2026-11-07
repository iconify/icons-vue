<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl-jarb6g.css';
import '../../css/c/cge_0eb5m.css';
import '../../css/d/db1p10rux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xl-jarb6g"/><path clip-rule="evenodd" class="cge_0eb5m"/><path class="db1p10rux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bomb-emoji-bold" /></template>

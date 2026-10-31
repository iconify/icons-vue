<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb49_cy3h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb49_cy3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:cherry-gloss" /></template>

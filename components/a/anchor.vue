<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zi3fumboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zi3fumboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:anchor" /></template>

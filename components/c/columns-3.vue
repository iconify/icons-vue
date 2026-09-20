<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b30w9ebxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b30w9ebxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:columns-3" /></template>

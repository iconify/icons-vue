<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iikt1teqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iikt1teqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:down-left-line" /></template>

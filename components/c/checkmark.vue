<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlv30xa8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlv30xa8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:checkmark" /></template>

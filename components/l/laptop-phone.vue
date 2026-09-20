<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ofvb_sb4h.css';
import '../../css/h/h-ft_9bvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofvb_sb4h"/><path clip-rule="evenodd" class="h-ft_9bvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:laptop-phone" /></template>

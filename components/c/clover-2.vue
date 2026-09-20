<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5of6ybso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x5of6ybso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:clover-2" /></template>

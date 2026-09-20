<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-sk7cc9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t-sk7cc9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:layout-bold" /></template>

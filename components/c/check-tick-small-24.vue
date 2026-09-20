<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/od96qpbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="od96qpbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:check-tick-small-24" /></template>

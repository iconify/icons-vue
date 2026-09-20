<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixth9-o6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixth9-o6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:favorite" /></template>

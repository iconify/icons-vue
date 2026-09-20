<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdrc-op-s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pdrc-op-s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:analysis" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_wfrqadw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="s_wfrqadw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:lion-filled" /></template>

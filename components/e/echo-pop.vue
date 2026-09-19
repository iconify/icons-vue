<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlj8iblgx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dlj8iblgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:echo-pop" /></template>

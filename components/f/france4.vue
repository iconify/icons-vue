<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/br9ibdxxo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="br9ibdxxo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:france4" /></template>

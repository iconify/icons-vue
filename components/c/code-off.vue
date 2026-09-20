<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/snfnpzbxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="snfnpzbxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:code-off" /></template>

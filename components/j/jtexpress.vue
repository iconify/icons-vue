<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/acem6c_hd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="acem6c_hd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:jtexpress" /></template>

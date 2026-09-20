<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsxbycckc.css';
import '../../css/i/i4nhh7ann.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dsxbycckc"/><path class="i4nhh7ann"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:foot-line" /></template>

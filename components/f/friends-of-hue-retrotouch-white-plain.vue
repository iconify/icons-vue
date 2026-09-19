<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ha_h-qiwd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ha_h-qiwd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:friends-of-hue-retrotouch-white-plain" /></template>

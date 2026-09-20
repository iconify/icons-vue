<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqo2ip6-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqo2ip6-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hackaday" /></template>

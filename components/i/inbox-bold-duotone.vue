<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6bs4k0fl.css';
import '../../css/y/yb3fr0bwr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6bs4k0fl"/><path class="yb3fr0bwr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:inbox-bold-duotone" /></template>

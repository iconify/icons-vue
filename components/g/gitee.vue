<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2435qy0i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2435qy0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gitee" /></template>

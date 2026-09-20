<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b44k8z_9l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b44k8z_9l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:iobroker" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qyuygn6di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="primary qyuygn6di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:flow-stored-data-duotone" /></template>

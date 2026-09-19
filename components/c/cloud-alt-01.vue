<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bwnrv3bqi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwnrv3bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:cloud-alt-01" /></template>

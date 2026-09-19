<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/md6o_9v8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md6o_9v8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:bus-filled" /></template>

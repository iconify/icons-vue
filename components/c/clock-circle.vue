<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsxu0ib6n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsxu0ib6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clock-circle" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dsewf9bad.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dsewf9bad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-up2-filled" /></template>

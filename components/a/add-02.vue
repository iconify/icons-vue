<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yff1h6byt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yff1h6byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:add-02" /></template>

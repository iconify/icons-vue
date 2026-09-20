<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yybhpcwne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="yybhpcwne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="wpf:add-user" /></template>

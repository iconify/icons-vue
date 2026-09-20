<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zz2l88b9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zz2l88b9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:harddisk-remove" /></template>

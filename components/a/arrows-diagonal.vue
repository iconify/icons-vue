<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a0m25c.css';
import '../../css/y/ytusak.css';
import '../../css/i/i9gq7u.css';
import '../../css/s/so-from-12.css';
import '../../css/s/so-to-0.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a0m25c ytusak"/><path class="a0m25c i9gq7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="line-md:arrows-diagonal" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-t-q3bzs.css';
import '../../css/s/s3ofesarg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b-t-q3bzs"/><path class="s3ofesarg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hive" /></template>

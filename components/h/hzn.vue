<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihmgd-bza.css';
import '../../css/x/x9845bcgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihmgd-bza"/><path class="x9845bcgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:hzn" /></template>

<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3b4blbrq.css';
import '../../css/b/bo9dr7buy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3b4blbrq"/><path class="bo9dr7buy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-flag-checkered" /></template>
